<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-hj91l4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-hj91l4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:payloadcms" /></template>
