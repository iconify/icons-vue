<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd50ifbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd50ifbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nintendogamecube" /></template>
