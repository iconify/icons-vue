<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic-ap717q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ic-ap717q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:x" /></template>
