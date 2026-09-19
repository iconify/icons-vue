<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j71l87b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j71l87b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:save2-fill" /></template>
