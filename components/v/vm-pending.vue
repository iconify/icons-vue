<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcf0dwdjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zcf0dwdjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:vm-pending" /></template>
