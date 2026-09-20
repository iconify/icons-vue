<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_d932o8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_d932o8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-minimalistic-outline" /></template>
