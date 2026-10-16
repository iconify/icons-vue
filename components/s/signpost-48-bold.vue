<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bun5sbcsa.css';
import '../../css/e/erw03p5yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bun5sbcsa"/><path class="erw03p5yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signpost-48-bold" /></template>
