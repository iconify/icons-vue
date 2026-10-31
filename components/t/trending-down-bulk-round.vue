<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3m13panc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3m13panc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-down-bulk-round" /></template>
