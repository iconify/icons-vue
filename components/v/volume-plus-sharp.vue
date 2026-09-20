<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3w5f94mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3w5f94mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-plus-sharp" /></template>
