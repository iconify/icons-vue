<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3lt31xms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3lt31xms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointer" /></template>
