<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvlgjsbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvlgjsbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-fill-round" /></template>
