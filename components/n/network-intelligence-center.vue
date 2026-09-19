<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx4navo8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx4navo8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:network-intelligence-center" /></template>
