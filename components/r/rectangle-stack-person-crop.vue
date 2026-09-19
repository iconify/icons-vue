<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq453ybdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zq453ybdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-stack-person-crop" /></template>
