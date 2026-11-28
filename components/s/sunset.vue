<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfs73vjug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfs73vjug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sunset" /></template>
