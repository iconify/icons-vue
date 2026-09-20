<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="p_zkco5dx"/><path class="etecrbbcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:ticket" /></template>
<style>
.etecrbbcf {
  d: path("M12.5 13a1 1 0 0 1 1 1v.5a1 1 0 1 1-2 0V14a1 1 0 0 1 1-1m0-8.5a1 1 0 0 1 1 1V6a1 1 0 1 1-2 0v-.5a1 1 0 0 1 1-1m0 2.75a1 1 0 0 1 1 1v.5a1 1 0 1 1-2 0v-.5a1 1 0 0 1 1-1m0 3a1 1 0 0 1 1 1v.5a1 1 0 1 1-2 0v-.5a1 1 0 0 1 1-1");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.p_zkco5dx {
  d: path("M1 6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2.64c0 .47-.282.894-.716 1.075a.309.309 0 0 0 0 .57c.434.18.716.604.716 1.074V14a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-2.64c0-.47.282-.894.716-1.075a.309.309 0 0 0 0-.57A1.16 1.16 0 0 1 1 8.641zm16 0H3v2.161c1.208.904 1.208 2.774 0 3.678V14h14v-2.161c-1.208-.905-1.208-2.774 0-3.678z");
}

</style>
