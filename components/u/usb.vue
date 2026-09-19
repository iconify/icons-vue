<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkjgxccjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kkjgxccjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:usb" /></template>
