<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6tshe-ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d6tshe-ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:medal-ribbon-with-star" /></template>
