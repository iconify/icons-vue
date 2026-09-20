<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdadk5ibk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdadk5ibk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-minimalistic-bold" /></template>
