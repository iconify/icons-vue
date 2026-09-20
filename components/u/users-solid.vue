<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxo396bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxo396bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:users-solid" /></template>
