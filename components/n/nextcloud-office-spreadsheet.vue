<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z13q2gbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z13q2gbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-spreadsheet" /></template>
