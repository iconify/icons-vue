<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyo179-vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyo179-vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-x-filled" /></template>
