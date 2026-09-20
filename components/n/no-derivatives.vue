<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyt30g5bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyt30g5bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:no-derivatives" /></template>
