<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9tks-8da.css';
import '../../css/f/flesb1b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9tks-8da"/><path class="flesb1b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:user-plus" /></template>
