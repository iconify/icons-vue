<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmkz1wbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmkz1wbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:talenthouse" /></template>
