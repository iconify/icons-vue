<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn-591bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jn-591bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shield-2" /></template>
