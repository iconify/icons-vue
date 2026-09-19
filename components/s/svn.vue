<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdi4zdbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdi4zdbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:svn" /></template>
