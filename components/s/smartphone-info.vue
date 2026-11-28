<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm6nef19u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm6nef19u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartphone-info" /></template>
