<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovw7vo7fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovw7vo7fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:shield-exclamation" /></template>
