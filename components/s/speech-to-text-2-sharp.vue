<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyjpndbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speech-to-text-2-sharp" /></template>
<style>
.jyjpndbru {
  fill: currentColor;
  d: path("M7.5 9.885q-.638 0-1.07-.432T6 8.385V4q0-.638.43-1.069T7.496 2.5q.618 0 1.06.431T9 4v4.385q0 .637-.44 1.068q-.442.431-1.06.431M7 15.5v-2.523q-1.833-.171-3.109-1.424Q2.616 10.3 2.616 8.5h1q0 1.52 1.163 2.51T7.5 12t2.721-.99t1.163-2.51h1q0 1.8-1.275 3.053Q9.833 12.806 8 12.977V15.5zM7 21v-3.27h9.5v-1h-6.115v-2H14.5v-1h-1.608q1.102-1.35 1.49-3.512t.387-4.102H11.5V3H20v18z");
}

</style>
