<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuq2gccji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tilde" /></template>
<style>
.cuq2gccji {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.776 14.303q1.19-4.361 4.264-4.976q2.79-.558 5.49 2.143q2.133 2.133 4.135 1.732q2.166-.433 3.111-3.899q.02-.072.053-.138t.078-.124t.101-.107t.12-.085t.134-.06t.143-.033q.074-.009.147-.004q.074.005.145.024q.144.04.262.131t.192.221t.093.277t-.02.292q-1.19 4.361-4.264 4.976q-2.79.558-5.49-2.143q-2.133-2.133-4.135-1.732q-2.166.433-3.111 3.899q-.02.072-.053.138t-.078.124t-.101.107t-.12.085t-.134.06t-.143.033t-.147.004t-.145-.024q-.072-.02-.138-.053t-.124-.078t-.107-.101t-.085-.12t-.06-.134t-.033-.143q-.009-.074-.004-.147q.005-.074.024-.145");
}

</style>
