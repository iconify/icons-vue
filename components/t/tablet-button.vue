<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amwc6obxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amwc6obxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:tablet-button" /></template>
