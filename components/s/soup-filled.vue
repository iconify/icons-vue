<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w09nt7o0v.css';
import '../../css/h/hkt82pb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w09nt7o0v"/><path class="hkt82pb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:soup-filled" /></template>
