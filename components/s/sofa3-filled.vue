<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iupiyvbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iupiyvbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sofa3-filled" /></template>
