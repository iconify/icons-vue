<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7chzchow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v7chzchow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rolled-curb-with-arrow-bottom-right" /></template>
