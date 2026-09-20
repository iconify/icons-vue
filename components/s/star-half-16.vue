<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd4g7om-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xd4g7om-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:star-half-16" /></template>
