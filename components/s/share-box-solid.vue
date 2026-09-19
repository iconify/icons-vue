<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/del6a6d2m.css';
import '../../css/l/lrkyxwbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="del6a6d2m"/><path class="lrkyxwbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:share-box-solid" /></template>
