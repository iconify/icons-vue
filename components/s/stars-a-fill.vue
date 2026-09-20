<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4rsa6bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4rsa6bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:stars-a-fill" /></template>
