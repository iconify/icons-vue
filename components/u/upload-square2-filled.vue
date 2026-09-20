<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnxue8ken.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnxue8ken"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:upload-square2-filled" /></template>
