<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1vyjvb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1vyjvb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pin-2-line" /></template>
