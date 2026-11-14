<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-z7srgum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:zigzag" /></template>
<style>
.x-z7srgum {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.4 14.55l4.5-6q.09-.119.218-.195t.276-.097t.292.015t.264.127q.086.064.15.15l3.9 5.2l3.9-5.2q.044-.059.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034t.147-.007t.145.022t.138.051t.126.076q.086.064.15.15l4.5 6q.09.119.127.264q.037.144.015.292t-.097.276t-.195.218t-.264.127t-.292.015t-.276-.097t-.218-.195l-3.9-5.2l-3.9 5.2q-.064.086-.15.15q-.059.044-.126.076q-.066.032-.138.051q-.071.018-.145.022t-.147-.007t-.143-.034q-.07-.025-.133-.063q-.064-.037-.119-.087t-.099-.108l-3.9-5.2l-3.9 5.2q-.09.119-.218.195t-.276.097t-.292-.015q-.145-.037-.264-.127t-.195-.218t-.097-.276t.015-.292t.127-.264");
}

</style>
