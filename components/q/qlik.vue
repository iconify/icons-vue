<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8069bgtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8069bgtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qlik" /></template>
