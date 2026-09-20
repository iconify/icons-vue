<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuol2-bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuol2-bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:twenty" /></template>
