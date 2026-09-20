<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4yn0ubey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-notes-outline-rounded" /></template>
<style>
.l4yn0ubey {
  fill: currentColor;
  d: path("M7.693 13.309q.23-.23.23-.54t-.23-.54t-.54-.229t-.538.23t-.23.54t.23.539t.539.23t.54-.23m0-2.77q.229-.23.229-.539t-.23-.54t-.54-.23t-.538.23t-.23.54t.23.54t.539.23t.54-.23m0-2.77q.229-.23.229-.54q0-.309-.23-.539t-.54-.23t-.538.23q-.23.23-.23.54t.23.54q.23.229.539.229t.54-.23m3.037 5.5H14q.214 0 .357-.144t.143-.357t-.143-.356t-.357-.144h-3.27q-.213 0-.356.144t-.143.356t.143.357t.357.143m0-2.769H17q.214 0 .357-.143T17.5 10t-.143-.357T17 9.5h-6.27q-.213 0-.356.143t-.143.357t.143.357t.357.143m0-2.77H17q.214 0 .357-.142t.143-.357t-.143-.357T17 6.731h-6.27q-.213 0-.356.143t-.143.357t.143.357t.357.143M6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.616 3h14.769q.69 0 1.153.463T21 4.616v10.769q0 .69-.462 1.153T19.385 17zm-.427-1h13.735q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03zM4 16V4z");
}

</style>
