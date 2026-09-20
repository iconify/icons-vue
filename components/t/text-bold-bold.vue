<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udb8obbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udb8obbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-bold" /></template>
