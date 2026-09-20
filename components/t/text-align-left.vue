<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-1y4eb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-1y4eb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-align-left" /></template>
