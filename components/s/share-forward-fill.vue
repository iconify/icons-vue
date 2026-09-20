<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9-rvbopt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9-rvbopt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-forward-fill" /></template>
