<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zujyr9_da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="zujyr9_da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:thumbs-down" /></template>
