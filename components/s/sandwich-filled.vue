<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2r7znbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2r7znbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sandwich-filled" /></template>
