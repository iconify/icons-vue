<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="b jgl3teb5k"/><path class="bj1nz5b9x"/><path class="b qw5wtx7ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wow" /></template>
<style>
.bj1nz5b9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.866 25.618c0 1.798 1.415 3.236 3.066 3.236c1.77 0 3.185-1.438 3.185-3.236v-3.236c0-1.798-1.416-3.236-3.185-3.236s-3.066 1.438-3.066 3.236z");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jgl3teb5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.935 19.266l-2.359 9.588l-2.358-9.588l-2.359 9.588L9.5 19.266");
}

.qw5wtx7ex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.5 19.266l-2.359 9.588l-2.359-9.588l-2.358 9.588l-2.359-9.588");
}

</style>
