<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unb5jhb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unb5jhb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-medium-sharp" /></template>
