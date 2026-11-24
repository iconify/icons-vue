<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g72-7bt9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g72-7bt9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mic-off-filled" /></template>
