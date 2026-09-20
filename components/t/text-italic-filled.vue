<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1jehmq7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1jehmq7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-italic-filled" /></template>
