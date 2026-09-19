<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynzxo5bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="ynzxo5bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:user-secret" /></template>
