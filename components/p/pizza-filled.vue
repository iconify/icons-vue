<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_xcrkbeg.css';
import '../../css/o/ojv9pubkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_xcrkbeg"/><path class="ojv9pubkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pizza-filled" /></template>
