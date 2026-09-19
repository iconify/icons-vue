<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb0ublros.css';
import '../../css/j/jwnh_illk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb0ublros"/><path class="jwnh_illk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-square" /></template>
