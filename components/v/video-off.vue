<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywepqte8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywepqte8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:video-off" /></template>
