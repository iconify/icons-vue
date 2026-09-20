<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsvk-rb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dsvk-rb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:trophy-16" /></template>
