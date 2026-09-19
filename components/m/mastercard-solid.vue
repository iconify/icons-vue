<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueptk5xjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ueptk5xjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mastercard-solid" /></template>
