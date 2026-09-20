<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwtn5pbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwtn5pbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-pan" /></template>
