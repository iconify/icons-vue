<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avgb43z_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avgb43z_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pin-1-solid" /></template>
