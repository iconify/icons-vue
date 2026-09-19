<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta27mrdhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="ta27mrdhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:tinder" /></template>
