<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9b_hg85a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9b_hg85a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:store-3-fill" /></template>
