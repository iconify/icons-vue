<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_l6o_b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_l6o_b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ticket-fill" /></template>
