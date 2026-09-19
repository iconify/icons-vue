<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqq4x7xuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uqq4x7xuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:stumbleupon-with-circle" /></template>
