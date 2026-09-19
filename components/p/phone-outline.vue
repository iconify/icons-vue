<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/butwtctap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="butwtctap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:phone-outline" /></template>
