<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdv-4ebbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdv-4ebbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:yak" /></template>
