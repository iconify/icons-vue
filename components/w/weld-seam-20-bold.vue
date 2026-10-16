<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/escqflblo.css';
import '../../css/o/otychb1vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="escqflblo"/><path class="otychb1vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weld-seam-20-bold" /></template>
