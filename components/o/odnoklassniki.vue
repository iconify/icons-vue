<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chpo8u4lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272,"height":432};
const content = `<path class="chpo8u4lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:odnoklassniki" /></template>
