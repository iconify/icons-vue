<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf80y80vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf80y80vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:text-align-center" /></template>
