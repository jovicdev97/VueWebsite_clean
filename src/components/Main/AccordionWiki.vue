<script setup lang="ts">
import { ref } from 'vue'
import { Tabs, Tab } from 'flowbite-vue'
const activeTab = ref('first')
</script>
<template>
  <tabs variant="pills" v-model="activeTab" class="p-5">
    <tab name="TTT" title="TTT">
      <ol>
	<li>Aber Kay, der kleine Kay! fragte Gerda. Wann kam er? Befand er sich unter der Menge?</li>
	<li>Eil mit Weile! nun sind wir gerade bei ihm! Am dritten Tage kam eine kleine Person, weder mit Pferd, noch mit Wagen, ganz lustig und guter Dinge gerade auf das Schloss hinaufspaziert. Seine Augen blitzten wie deine, er hatte prächtiges langes Haar, aber sonst ärmliche Kleider.</li>
	<li>Da war Kay! jubelte Gerda. O, dann habe ich ihn gefunden und dabei klatschte sie in die Hände.
</li>
	<li>Er hatte einen kleinen Ranzen auf seinem Rücken! sagte die Krähe.</li>
	<li>Nein, das war sicherlich sein Schlitten! sagte Gerda, denn damit ging er fort!</li>
</ol>
    </tab>
    <tab name="Jail" title="Jail">
            <ol>
	<li>Aber Kay, der kleine Kay! fragte Gerda. Wann kam er? Befand er sich unter der Menge?</li>
	<li>Eil mit Weile! nun sind wir gerade bei ihm! Am dritten Tage kam eine kleine Person, weder mit Pferd, noch mit Wagen, ganz lustig und guter Dinge gerade auf das Schloss hinaufspaziert. Seine Augen blitzten wie deine, er hatte prächtiges langes Haar, aber sonst ärmliche Kleider.</li>
	<li>Da war Kay! jubelte Gerda. O, dann habe ich ihn gefunden und dabei klatschte sie in die Hände.
</li>
	<li>Er hatte einen kleinen Ranzen auf seinem Rücken! sagte die Krähe.</li>
	<li>Nein, das war sicherlich sein Schlitten! sagte Gerda, denn damit ging er fort!</li>
</ol>
    </tab>
    <tab name="Surf" title="Surf">
      <dl>
	<dt>Definitionsliste</dt>
	<dd>Ja, das habe ich gesehen! riefen beide Kinder, und nun wussten sie, dass es Wahrheit wäre.</dd>
	<dt>Kann die Schneekönigin hereinkommen? fragte das kleine Mädchen.</dt>
	<dd>Lass sie nur kommen, sagte der Knabe, dann setze ich sie auf den warmen Kachelofen und sie muss zerschmelzen!</dd>
</dl>
    </tab>
    <tab name="fourth" title="Fourth" :disabled="false">
      <h1>Header Level 1</h1>
<p><strong>Auf dem letzten Hause eines kleinen Dörfchens</strong> befand sich ein <abbr title="Behausung eines langbeinigen Vogels">Storchnest</abbr>. Die Storchmutter saß im Neste bei ihren vier Jungen, welche den Kopf mit dem kleinen <em>schwarzen Schnabel</em>, denn er war noch nicht rot geworden, hervorstreckten. Ein Stückchen davon stand auf der Dachfirste starr und steif der Storchvater <code>syntax</code>. Man hätte meinen können, er wäre aus Holz gedrechselt, so stille stand er. „Gewiss sieht es recht vornehm aus, dass meine Frau eine Schildwache bei dem Neste hat!“ dachte er. Und er stand unermüdlich auf <a href="#nirgendwo" title="Title für einem Bein">einem Beine</a>.</p>
<h2>Header Level 2</h2>
<ol>
	<li>Und was dann? fragten die Storchkinder.</li>
	<li>Dann werden wir aber doch gepfählt, wie die Knaben behaupteten, und höre nur, jetzt sagen sie es schon wieder!</li>
</ol>
<p>Unten auf der Straße spielte eine Schar Kinder und als sie die Störche erblickten, sang einer der dreistesten Knaben und allmählich allezus.einen Vers aus einem alten Storchliede, so gut sie sich dessen erinnern konnten:</p>
<blockquote cite="Hans Andersen">
	<p>Störchlein, Störchlein, fliege,<br />Damit ich dich nicht kriege, <br />Deine Frau, die liegt im Neste dein Bei deinen lieben Kindelein: Das eine wird gepfählt, Das andere wird abgekehlt, Das dritte wird verbrannt, Das vierte dir entwandt!</p>
	<p><cite>Hans Andersen</cite></p>
</blockquote>
<p>Höre nur, was die Jungen singen! sagten die kleinen Storchkinder. Sie sagen, wir sollen gebraten und verbrannt werden!</p>
<h3>Header Level 3</h3>
<ul>
	<li>Das eine wird gepfählt</li>
	<li>Das andere wird abgekehlt!</li>
</ul>
<pre><code>
#header h1 a { display: block; width: 300px; height: 80px; }
</code></pre>
    </tab>
  </tabs>
</template>