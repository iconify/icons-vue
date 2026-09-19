<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzbsxqb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lzbsxqb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:twitter" /></template>
