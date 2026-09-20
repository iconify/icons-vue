<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz6-4v4mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xz6-4v4mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shaarli-light" /></template>
