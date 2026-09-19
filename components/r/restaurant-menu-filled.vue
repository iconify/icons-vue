<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmqa5hbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmqa5hbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:restaurant-menu-filled" /></template>
