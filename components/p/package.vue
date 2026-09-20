<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udrshjblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="udrshjblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:package" /></template>
