<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_btfpb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":558,"height":770};
const content = `<path class="z_btfpb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sleipnir" /></template>
