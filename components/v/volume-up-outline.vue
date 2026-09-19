<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7e_m-v8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7e_m-v8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:volume-up-outline" /></template>
