<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teponxbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teponxbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:minus-circle-filled" /></template>
