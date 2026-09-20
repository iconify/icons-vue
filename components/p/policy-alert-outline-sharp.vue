<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd1fok1yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:policy-alert-outline-sharp" /></template>
<style>
.kd1fok1yw {
  fill: currentColor;
  d: path("M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615v4.539h-1V6.375l-6-2.23l-6 2.23V11.1q0 3.025 1.7 5.5t4.3 3.3q.65-.2 1.238-.512t1.162-.738l.63.746q-.747.54-1.45.916q-.703.375-1.58.65m7.913-.105q-.144-.143-.144-.357t.144-.357t.356-.143t.357.143t.143.357t-.143.357t-.357.143t-.356-.143m-.144-3.241v-5h1v5zm-6.356-4.203Q14 12.825 14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14t1.413-.587M12 15q-1.246 0-2.123-.877T9 12t.877-2.123T12 9t2.123.877T15 12q0 .454-.137.89q-.138.435-.374.814l2.878 2.873l-.713.713l-2.885-2.879q-.373.295-.828.442T12 15");
}

</style>
