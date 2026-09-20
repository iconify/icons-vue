<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0k-_7b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0k-_7b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-sharepoint-2013-dark" /></template>
