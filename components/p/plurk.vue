<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izwngpo4z.css';
import '../../css/w/w8fd4ubay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="izwngpo4z"/><path class="w8fd4ubay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:plurk" /></template>
