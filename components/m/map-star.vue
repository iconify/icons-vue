<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsa0n1bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsa0n1bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-star" /></template>
