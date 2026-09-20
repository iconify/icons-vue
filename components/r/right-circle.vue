<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x359nsadw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x359nsadw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:right-circle" /></template>
