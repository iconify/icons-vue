<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw8fblbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw8fblbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tshirt-filled" /></template>
