<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcbuc8xts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcbuc8xts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:orchard-core" /></template>
