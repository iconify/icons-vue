<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awox36b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="awox36b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pager-solid" /></template>
