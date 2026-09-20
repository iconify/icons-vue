<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttzsxibhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ttzsxibhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tambourine-16" /></template>
