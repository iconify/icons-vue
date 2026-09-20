<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzp4s85tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vzp4s85tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-down-outline" /></template>
