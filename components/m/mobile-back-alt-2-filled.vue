<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmb10tbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmb10tbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-back-alt-2-filled" /></template>
