<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahbxdqfbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahbxdqfbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-heart-fill" /></template>
