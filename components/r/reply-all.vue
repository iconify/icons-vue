<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgfyvbb5e.css';
import '../../css/u/ud8i2ab-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zgfyvbb5e"/><path class="ud8i2ab-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:reply-all" /></template>
