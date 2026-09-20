<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxwz7_bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwz7_bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-2-line" /></template>
