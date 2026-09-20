<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utlw1rbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utlw1rbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:separator" /></template>
