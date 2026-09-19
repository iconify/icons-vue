<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsthawb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tsthawb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:shopping-basket" /></template>
