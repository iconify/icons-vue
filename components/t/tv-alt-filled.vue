<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isbbe3e6v.css';
import '../../css/y/ynshwsq7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isbbe3e6v"/><rect class="ynshwsq7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tv-alt-filled" /></template>
