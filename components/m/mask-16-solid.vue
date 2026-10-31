<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs3hx5zyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zs3hx5zyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:mask-16-solid" /></template>
