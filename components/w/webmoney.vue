<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqbu28e1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqbu28e1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webmoney" /></template>
