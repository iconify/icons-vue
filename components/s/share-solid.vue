<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj7w2f4dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj7w2f4dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:share-solid" /></template>
