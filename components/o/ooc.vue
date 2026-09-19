<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afh5eih4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":387,"height":512};
const content = `<path class="afh5eih4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ooc" /></template>
