<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtu5bdc_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtu5bdc_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rain-fill" /></template>
