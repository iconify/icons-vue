<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sozw1eb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sozw1eb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:navigation-solid" /></template>
