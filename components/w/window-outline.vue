<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5smb1yju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5smb1yju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:window-outline" /></template>
