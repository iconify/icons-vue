<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr7kmbczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mustache" /></template>
<style>
.zr7kmbczw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.938 8.409q1.82-.152 3.062.977q1.242-1.129 3.062-.977q2.236.186 3.562 2.175q.835 1.225 2.097.72q.069-.028.142-.041t.146-.013q.074.001.146.016q.073.016.14.045t.129.071t.113.094t.092.115q.04.062.067.13q.05.124.054.257t-.038.259q-.835 2.503-3.388 3.205q-2.314.636-4.221-.556q-1.165-.757-2.103-1.602q-.936.844-2.091 1.595q-1.919 1.199-4.233.563q-2.553-.702-3.388-3.205q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137t.079-.125t.101-.107t.12-.085t.134-.06q.126-.042.259-.038t.257.054q1.262.505 2.101-.727q1.322-1.982 3.558-2.168");
}

</style>
