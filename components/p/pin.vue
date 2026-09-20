<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdq8rzv_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdq8rzv_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:pin" /></template>
