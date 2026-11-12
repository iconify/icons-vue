<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7avtxd7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touch-double-2-hold-outline-sharp" /></template>
<style>
.f7avtxd7o {
  fill: currentColor;
  d: path("m3.006 9.514l-.97.282q-.03-.198-.043-.395q-.012-.198-.012-.395q0-2.925 2.033-4.966Q6.048 2 8.978 2t4.976 2.04T16 9.006q0 .147-.003.279l-.008.28l-1.008-.423q.023-1.205-.387-2.257T13.46 5.012q-.826-.914-1.97-1.463T8.98 3q-2.5 0-4.25 1.757T2.98 9.006q0 .136.01.25q.01.115.016.258m2.802-.897l-1.02.314q.016-.87.34-1.616q.324-.748.903-1.3q.56-.557 1.317-.892q.758-.335 1.633-.335q.255 0 .502.03t.494.097l-.323.952q-.168-.034-.328-.056q-.16-.023-.345-.023q-1.225 0-2.126.815q-.901.814-1.047 2.014M9.244 21l-5.613-7.165L4.666 12.8l3.392 2.079V7.692h1v8.98l-3.7-2.231L9.719 20H18v-7.52h-3.404v-1H19V21zm2.083-8.52V6.193h1v6.289zm.352 3.5");
}

</style>
