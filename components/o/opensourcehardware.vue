<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mngl0bcck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mngl0bcck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opensourcehardware" /></template>
