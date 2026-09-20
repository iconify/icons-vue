<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnwb_mbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lnwb_mbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-playing-soccer" /></template>
