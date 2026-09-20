<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2dbied0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2dbied0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:send-fill" /></template>
