<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weyu_8bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="weyu_8bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:taxi" /></template>
