<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq_eunbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lq_eunbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:maximize-16" /></template>
