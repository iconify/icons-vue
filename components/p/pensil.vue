<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu0rrrp-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xu0rrrp-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:pensil" /></template>
