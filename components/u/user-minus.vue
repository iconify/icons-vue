<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn7w4tbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bn7w4tbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-minus" /></template>
