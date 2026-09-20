<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjxj44lwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jjxj44lwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:mermaid" /></template>
