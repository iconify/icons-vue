<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h08u19bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h08u19bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sticker-mule" /></template>
