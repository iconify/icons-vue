<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5hql90sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="w5hql90sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-27" /></template>
