<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnetsu-me.css';
import '../../css/j/j7goiubdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":619};
const content = `<path class="vnetsu-me"/><path class="j7goiubdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:orildo" /></template>
