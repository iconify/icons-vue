<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6vkwswbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o6vkwswbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-swimming-in-water" /></template>
