<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-qtrrb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y-qtrrb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:share-alt2" /></template>
