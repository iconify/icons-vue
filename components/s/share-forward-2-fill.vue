<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9g545mxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9g545mxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-forward-2-fill" /></template>
