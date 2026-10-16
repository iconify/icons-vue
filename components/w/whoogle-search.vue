<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6o3ktbcu.css';
import '../../css/w/wjyxzxbul.css';
import '../../css/y/yj4lhpb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1028,"height":254};
const content = `<path class="x6o3ktbcu"/><path class="wjyxzxbul"/><path class="yj4lhpb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whoogle-search" /></template>
