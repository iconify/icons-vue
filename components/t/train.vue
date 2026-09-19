<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mao0xgwut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mao0xgwut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:train" /></template>
