<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-o1g81ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-o1g81ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:menu-alt-03" /></template>
