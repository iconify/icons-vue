<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxc5to3rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxc5to3rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:texture-filled" /></template>
