<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx2gfdbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx2gfdbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plug2" /></template>
