<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v75zvrbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v75zvrbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-exclamation" /></template>
