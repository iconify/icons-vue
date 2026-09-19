<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx1zurbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx1zurbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:scheduled" /></template>
