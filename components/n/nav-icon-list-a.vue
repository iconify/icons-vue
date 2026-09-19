<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s189b_bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="s189b_bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nav-icon-list-a" /></template>
