<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzjyi_b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qzjyi_b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:trophy" /></template>
