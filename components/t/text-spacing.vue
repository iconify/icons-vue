<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjmafqb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjmafqb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text-spacing" /></template>
