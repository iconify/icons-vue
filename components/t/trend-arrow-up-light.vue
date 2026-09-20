<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7gtsxy4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7gtsxy4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:trend-arrow-up-light" /></template>
