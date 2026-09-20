<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywxc_u7nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ywxc_u7nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:xrp-circle-remix" /></template>
