<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxc6n7fcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxc6n7fcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:user-check" /></template>
