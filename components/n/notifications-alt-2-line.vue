<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf3saabbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf3saabbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:notifications-alt-2-line" /></template>
