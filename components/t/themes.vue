<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngv5_zdhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngv5_zdhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:themes" /></template>
