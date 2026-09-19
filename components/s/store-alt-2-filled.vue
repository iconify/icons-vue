<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hznzg0bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hznzg0bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:store-alt-2-filled" /></template>
