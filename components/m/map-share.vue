<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr0-jzmcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr0-jzmcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-share" /></template>
