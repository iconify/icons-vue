<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxll8bc5o.css';
import '../../css/y/y4i3220kc.css';
import '../../css/z/zkdyo_ief.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mxll8bc5o"/><path class="y4i3220kc"/><path class="zkdyo_ief"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:users-plus-20" /></template>
