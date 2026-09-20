<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6g0jxblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p6g0jxblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:navigation-right-hide" /></template>
