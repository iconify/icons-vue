<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg_qm-3fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zg_qm-3fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-standing-dress" /></template>
