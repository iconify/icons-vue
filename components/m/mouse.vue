<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8-k7-a4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8-k7-a4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:mouse" /></template>
