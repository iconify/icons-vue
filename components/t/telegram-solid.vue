<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_4pe5bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_4pe5bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:telegram-solid" /></template>
