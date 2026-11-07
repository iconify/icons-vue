<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgk4i-bav.css';
import '../../css/z/z3p-nc5qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgk4i-bav"/><path clip-rule="evenodd" class="z3p-nc5qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-2-bold" /></template>
