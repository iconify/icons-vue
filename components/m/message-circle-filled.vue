<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pppqz8-bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pppqz8-bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-filled" /></template>
