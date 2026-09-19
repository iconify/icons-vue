<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcfak91qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcfak91qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:thumbs-down" /></template>
