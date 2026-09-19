<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqtu6jxpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lqtu6jxpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:shield" /></template>
