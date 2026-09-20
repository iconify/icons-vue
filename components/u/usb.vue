<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay-_lhcfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ay-_lhcfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:usb" /></template>
