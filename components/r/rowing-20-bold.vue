<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqqbf4jvf.css';
import '../../css/f/flpc-e6db.css';
import '../../css/e/e6txgee1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zqqbf4jvf"/><path class="flpc-e6db"/><path class="e6txgee1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rowing-20-bold" /></template>
