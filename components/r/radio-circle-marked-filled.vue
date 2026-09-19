<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doumpmbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doumpmbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radio-circle-marked-filled" /></template>
