<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iemz6buzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iemz6buzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shopping-basket-2" /></template>
