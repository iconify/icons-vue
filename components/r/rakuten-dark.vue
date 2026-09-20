<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sydg7eklb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sydg7eklb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rakuten-dark" /></template>
