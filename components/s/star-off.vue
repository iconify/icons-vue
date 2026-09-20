<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl2na2b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl2na2b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:star-off" /></template>
