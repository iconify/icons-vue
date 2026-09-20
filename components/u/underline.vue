<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylrk2f8-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylrk2f8-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:underline" /></template>
