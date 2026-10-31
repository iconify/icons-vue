<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdgx7fuwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdgx7fuwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-more-horizontal-round" /></template>
