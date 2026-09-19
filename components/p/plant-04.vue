<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irnkvnbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irnkvnbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plant-04" /></template>
