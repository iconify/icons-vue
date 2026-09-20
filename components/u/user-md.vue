<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xma9i4bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xma9i4bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:user-md" /></template>
