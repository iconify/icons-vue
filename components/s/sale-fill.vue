<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb184ky8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb184ky8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sale-fill" /></template>
