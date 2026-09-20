<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygmjvmbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-outline-rounded" /></template>
<style>
.ygmjvmbki {
  fill: currentColor;
  d: path("M10.577 12.423Q10 11.846 10 11V5q0-.846.577-1.423T12 3t1.423.577T14 5v6q0 .846-.577 1.423T12 13t-1.423-.577M11.5 20v-3.017q-2.165-.19-3.716-1.72q-1.551-1.529-1.748-3.738q-.03-.214.11-.37Q6.286 11 6.5 11t.357.153t.185.366q.197 1.923 1.623 3.202T12 16q1.935 0 3.348-1.291q1.413-1.292 1.61-3.19q.042-.213.185-.366T17.5 11t.354.156t.11.369q-.197 2.16-1.735 3.704T12.5 16.983V20q0 .214-.143.357T12 20.5t-.357-.143T11.5 20m1.213-8.287Q13 11.425 13 11V5q0-.425-.288-.712T12 4t-.712.288T11 5v6q0 .425.288.713T12 12t.713-.288");
}

</style>
