<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwy6e0b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwy6e0b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rows-two-alt" /></template>
