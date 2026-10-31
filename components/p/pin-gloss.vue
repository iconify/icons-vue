<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsp7bnb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsp7bnb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pin-gloss" /></template>
