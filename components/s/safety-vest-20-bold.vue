<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9-064bdl.css';
import '../../css/l/lxjm5vb4n.css';
import '../../css/n/n61va8bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m9-064bdl"/><path class="lxjm5vb4n"/><path class="n61va8bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safety-vest-20-bold" /></template>
