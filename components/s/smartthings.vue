<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu2g9iiqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu2g9iiqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:smartthings" /></template>
