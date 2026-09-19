<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-1bhwrax"/><path class="q0s_atbta"/><path class="zl7jpcc2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:public-services-culture" /></template>
<style>
.f-1bhwrax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.752 26.697s.981 2 3.28 2.617c2.3.616 4.15-.626 4.15-.626m-.548-6.583c1.231-.753 2.78-.21 3.614.969M19.675 20.24c1.23-.754 2.78-.211 3.614.968");
}

.q0s_atbta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.84 13.387l-2.554 10.217c-1.04 4.167.32 8.16 6.097 11.407c6.628.077 9.8-2.701 10.983-6.83l2.899-10.125s-3.424-2.246-8.381-3.574s-9.046-1.095-9.046-1.095z");
}

.zl7jpcc2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.057 24c0 9.255-1.21 11.402-9.03 16.03c-7.817 4.627-10.237 4.627-18.055 0c-7.82-4.628-9.029-6.775-9.029-16.03s1.21-11.402 9.03-16.03c7.817-4.627 10.237-4.627 18.055 0c7.82 4.628 9.029 6.775 9.029 16.03");
}

</style>
