<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-yg1pedr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-yg1pedr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:phone-solid" /></template>
