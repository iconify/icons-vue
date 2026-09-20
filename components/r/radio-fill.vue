<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb7k0tb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb7k0tb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:radio-fill" /></template>
