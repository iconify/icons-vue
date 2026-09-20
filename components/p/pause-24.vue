<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n75uy8bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n75uy8bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pause-24" /></template>
