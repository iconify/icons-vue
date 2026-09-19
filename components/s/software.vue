<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duy9jjbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="duy9jjbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:software" /></template>
