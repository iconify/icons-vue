<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/schqrjbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="schqrjbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vk" /></template>
