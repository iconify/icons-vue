<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5i8bacxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5i8bacxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:play-circle-filled" /></template>
