<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6r28jcem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6r28jcem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:slack" /></template>
