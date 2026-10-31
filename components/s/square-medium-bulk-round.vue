<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blzmcibqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blzmcibqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-medium-bulk-round" /></template>
