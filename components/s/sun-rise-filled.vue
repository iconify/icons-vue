<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-6509ckr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-6509ckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-rise-filled" /></template>
