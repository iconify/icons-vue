<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_hcr-bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_hcr-bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:terser" /></template>
