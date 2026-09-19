<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaqr3fw9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zaqr3fw9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:windy-dust" /></template>
