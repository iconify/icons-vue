<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvi1ht2vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="zvi1ht2vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:rss" /></template>
