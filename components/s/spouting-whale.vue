<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssjp49gnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ssjp49gnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:spouting-whale" /></template>
