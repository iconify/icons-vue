<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_my8fiag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b_my8fiag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:warning" /></template>
