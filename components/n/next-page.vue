<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj7--_fqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj7--_fqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:next-page" /></template>
