<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v7kunqb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-dismiss-48-filled" /></template>
<style>
.v7kunqb3r {
  fill: currentColor;
  d: path("M23.135 4.348a1.25 1.25 0 0 1 1.73 0c2.758 2.643 6.685 4.078 10.037 4.84c1.66.376 3.14.58 4.203.69a29 29 0 0 0 1.654.122h.02A1.25 1.25 0 0 1 42 11.25V21c0 9.497-5.06 19.016-17.627 22.943a1.25 1.25 0 0 1-.746 0c-6.238-1.95-10.668-5.293-13.53-9.419C7.244 30.408 6 25.587 6 20.75v-9.5A1.25 1.25 0 0 1 7.22 10h.021a9 9 0 0 0 .408-.02c.29-.017.716-.047 1.247-.102a36 36 0 0 0 4.202-.69c3.352-.762 7.278-2.197 10.037-4.84m8.499 12.018a1.25 1.25 0 0 0-1.768 0L24 22.232l-5.866-5.866a1.25 1.25 0 0 0-1.768 1.768L22.232 24l-5.866 5.866a1.25 1.25 0 0 0 1.768 1.768L24 25.768l5.866 5.866a1.25 1.25 0 0 0 1.768-1.768L25.768 24l5.866-5.866a1.25 1.25 0 0 0 0-1.768");
}

</style>
