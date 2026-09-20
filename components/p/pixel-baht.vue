<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_vfzqrtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l_vfzqrtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-baht" /></template>
