<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5i8mrb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5i8mrb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-smile-fill" /></template>
