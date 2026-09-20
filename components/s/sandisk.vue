<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjnsgx13d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjnsgx13d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sandisk" /></template>
