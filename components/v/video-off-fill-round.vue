<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qut7gns8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qut7gns8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-fill-round" /></template>
