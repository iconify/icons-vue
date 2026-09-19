<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3v4iib0v.css';
import '../../css/l/l97nb-quh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3v4iib0v"/><circle class="l97nb-quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:wifi-1" /></template>
