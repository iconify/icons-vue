<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygz__nb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygz__nb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-right-2-fill" /></template>
