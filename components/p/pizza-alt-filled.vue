<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojv9pubkm.css';
import '../../css/h/hur7hdsnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojv9pubkm"/><path class="hur7hdsnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pizza-alt-filled" /></template>
