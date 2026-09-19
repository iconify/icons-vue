<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqeh_xbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqeh_xbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:traffic-cone-filled" /></template>
