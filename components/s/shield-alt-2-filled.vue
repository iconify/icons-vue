<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih0i_2fow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0i_2fow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-alt-2-filled" /></template>
