<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyq_xjgvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hyq_xjgvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:vote" /></template>
