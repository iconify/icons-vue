<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhfnc2dzw.css';
import '../../css/c/ccz24ggpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhfnc2dzw"/><path class="ccz24ggpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:myheats-dark" /></template>
