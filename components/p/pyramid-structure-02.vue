<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf8489bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf8489bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pyramid-structure-02" /></template>
