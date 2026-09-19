<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rddng9bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rddng9bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:vk-with-circle" /></template>
