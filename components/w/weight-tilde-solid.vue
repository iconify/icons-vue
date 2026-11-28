<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg0h9m8rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0h9m8rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:weight-tilde-solid" /></template>
