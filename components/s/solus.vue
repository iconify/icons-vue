<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcs_icv0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcs_icv0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:solus" /></template>
