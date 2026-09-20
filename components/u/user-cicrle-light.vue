<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/pwbt2qflx.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/g/giihlsblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="pwbt2qflx"/><circle class="m4l-9ybuj"/><path class="giihlsblf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-cicrle-light" /></template>
