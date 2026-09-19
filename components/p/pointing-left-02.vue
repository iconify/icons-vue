<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zncj4gwdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zncj4gwdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-left-02" /></template>
