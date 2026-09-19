<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc6t70b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uc6t70b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:spotify" /></template>
