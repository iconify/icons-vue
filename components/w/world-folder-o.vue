<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amb6xmb9p.css';
import '../../css/b/bt5hmxdsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="amb6xmb9p"/><path class="bt5hmxdsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:world-folder-o" /></template>
