<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn6ok5j4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stable" /></template>
<style>
.yn6ok5j4k {
  fill: var(--svg-color--001e1e, #001e1e);
  d: path("M11.989 12.826c.743-.45 1.802-1.074 2.635-1.074c1.333 0 2.448.944 2.448 2.737c0 2.861-3.4 5.498-8.206 4.35a.026.026 0 0 0-.031.024v1.546q0 .017.016.024a9 9 0 0 0 2.088.505c5.63.662 10.494-4.035 10.03-9.685a8.83 8.83 0 0 0-1.564-4.37q-.01-.017-.035-.007l-7.377 4.264c-.838.478-1.802 1.076-2.634 1.076c-1.333 0-2.448-.943-2.448-2.736c0-2.861 3.401-5.498 8.207-4.35a.025.025 0 0 0 .03-.024V3.584q0-.016-.015-.024A9 9 0 0 0 4.572 17.081a.024.024 0 0 0 .033.008z");
}

</style>
