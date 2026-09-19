<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-6av_bac.css';
import '../../css/g/gw0lhg8wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-6av_bac"/><path class="gw0lhg8wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:usb" /></template>
