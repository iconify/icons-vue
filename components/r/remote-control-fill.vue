<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej4wkabvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej4wkabvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:remote-control-fill" /></template>
