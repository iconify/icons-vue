<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx1tun3fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx1tun3fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-circle-solid" /></template>
