<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3c-6wbuu.css';
import '../../css/d/dq11ufbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d3c-6wbuu"/><path class="dq11ufbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:previous" /></template>
