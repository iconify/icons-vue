<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sba_tzbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sba_tzbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:maze" /></template>
