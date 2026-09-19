<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhpwlgmyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhpwlgmyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music-alt-filled" /></template>
