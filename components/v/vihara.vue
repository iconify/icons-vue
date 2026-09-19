<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xejpd7b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xejpd7b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vihara" /></template>
