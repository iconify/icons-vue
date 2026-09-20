<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slfr786iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slfr786iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seedling" /></template>
