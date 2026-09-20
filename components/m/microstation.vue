<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1vqpjv6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1vqpjv6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microstation" /></template>
