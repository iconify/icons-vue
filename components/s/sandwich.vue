<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz5p2db5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz5p2db5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sandwich" /></template>
