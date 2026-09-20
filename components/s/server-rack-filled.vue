<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkj3fvbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkj3fvbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:server-rack-filled" /></template>
