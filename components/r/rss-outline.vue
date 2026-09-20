<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1587abkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v1587abkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rss-outline" /></template>
