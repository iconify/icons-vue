<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hng-1kbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hng-1kbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sale-filled" /></template>
