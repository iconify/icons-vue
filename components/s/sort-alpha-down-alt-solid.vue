<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1it6dm-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j1it6dm-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sort-alpha-down-alt-solid" /></template>
