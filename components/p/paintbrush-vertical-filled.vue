<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr_n6nb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr_n6nb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:paintbrush-vertical-filled" /></template>
