<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_88s3cmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l_88s3cmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-paddling-canoe-on-water" /></template>
