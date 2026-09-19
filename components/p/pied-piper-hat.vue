<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xikwt1jtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xikwt1jtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pied-piper-hat" /></template>
