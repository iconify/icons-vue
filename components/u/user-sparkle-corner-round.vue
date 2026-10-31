<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzoallehr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzoallehr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-sparkle-corner-round" /></template>
