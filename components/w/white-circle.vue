<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htu6zoakn.css';
import '../../css/s/snpiwsb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="htu6zoakn"/><circle class="snpiwsb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-circle" /></template>
