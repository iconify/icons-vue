<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t19d__biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":222};
const content = `<path class="t19d__biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:material-ui" /></template>
