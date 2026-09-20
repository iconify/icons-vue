<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv6pjmbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv6pjmbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:navigation-menu-bold" /></template>
