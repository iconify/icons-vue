<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptah8jequ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ptah8jequ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:one-over-water" /></template>
