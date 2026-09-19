<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix5oy4d5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix5oy4d5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:send-alt-2" /></template>
