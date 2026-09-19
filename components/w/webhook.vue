<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjblqxbkz.css';
import '../../css/m/mhg07abei.css';
import '../../css/j/jamog_u4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjblqxbkz"/><path class="mhg07abei"/><path class="jamog_u4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:webhook" /></template>
