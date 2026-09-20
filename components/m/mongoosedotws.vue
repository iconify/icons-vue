<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgh6pkben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgh6pkben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mongoosedotws" /></template>
