<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz_11uu-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_11uu-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tunein" /></template>
