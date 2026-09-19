<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt-hjub7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xt-hjub7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:v" /></template>
