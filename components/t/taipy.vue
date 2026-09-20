<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjn7-gbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjn7-gbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:taipy" /></template>
