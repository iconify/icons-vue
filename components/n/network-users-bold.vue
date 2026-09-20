<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi_o19b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_o19b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:network-users-bold" /></template>
