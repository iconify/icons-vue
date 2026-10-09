<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewn1ke3br.css';
import '../../css/e/e3k76dbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="e3k76dbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sidebar-20" /></template>
