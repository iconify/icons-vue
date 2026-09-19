<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h75wxuipw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h75wxuipw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:text-arrows-up-down" /></template>
