<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eer4ttwsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eer4ttwsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:store" /></template>
