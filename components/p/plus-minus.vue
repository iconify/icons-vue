<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojj3akbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojj3akbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:plus-minus" /></template>
