<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmqnm6b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mmqnm6b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:text-align-middle" /></template>
