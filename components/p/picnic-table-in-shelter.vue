<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr938p2vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yr938p2vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:picnic-table-in-shelter" /></template>
