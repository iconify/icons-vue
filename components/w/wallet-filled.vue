<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4h_m-qgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v4h_m-qgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:wallet-filled" /></template>
