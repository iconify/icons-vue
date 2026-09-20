<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_l8lhbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_l8lhbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:starburst-outline" /></template>
