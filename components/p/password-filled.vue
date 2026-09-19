<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-fuf2bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-fuf2bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:password-filled" /></template>
