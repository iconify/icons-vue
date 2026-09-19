<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwyplh1_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwyplh1_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:purchase-tag" /></template>
