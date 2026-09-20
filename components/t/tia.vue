<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ekkmkdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5ekkmkdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tia" /></template>
