<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5s6a10qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5s6a10qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-alert" /></template>
