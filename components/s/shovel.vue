<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbot78qwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="rbot78qwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shovel" /></template>
