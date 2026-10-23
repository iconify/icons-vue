<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te-6zluiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te-6zluiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:syringe" /></template>
