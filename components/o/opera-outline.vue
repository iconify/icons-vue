<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hii5eibzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hii5eibzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:opera-outline" /></template>
