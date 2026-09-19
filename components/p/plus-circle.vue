<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_gf1l17f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_gf1l17f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:plus-circle" /></template>
