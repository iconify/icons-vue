<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoer9n1kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uoer9n1kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize-square2-filled" /></template>
