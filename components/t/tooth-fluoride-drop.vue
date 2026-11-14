<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o29pg6b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-fluoride-drop" /></template>
<style>
.o29pg6b3f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.414 1.781q.052-.065.117-.117q.117-.093.26-.134t.292-.025q.148.016.279.088q.13.072.224.188q.167.21.501.613Q14.75 4.401 14.75 5.5q0 2.75-2.75 2.75T9.25 5.5q0-1.099 1.663-3.106q.334-.403.501-.613m-1.336 7.025Q8.671 8 7.75 8q-4 0-4 4.25q0 1.479 1.109 3.374q.509.87.671 1.338l.992 3.97q.33 1.318 1.728 1.318q1.387 0 1.722-1.297l.995-3.232l.011-.039Q11.023 17.5 12 17.5t1.022.182l.011.039l.995 3.232q.335 1.297 1.722 1.297q1.398 0 1.728-1.318l.992-3.97q.162-.468.671-1.338q1.109-1.895 1.109-3.374q0-4.25-4-4.25q-.921 0-2.328.806Q12.709 9.5 12 9.5t-1.922-.694");
}

</style>
