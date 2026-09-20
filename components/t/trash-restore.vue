<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp8tg7byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tp8tg7byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:trash-restore" /></template>
