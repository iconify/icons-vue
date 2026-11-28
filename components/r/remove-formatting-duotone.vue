<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myq6b2b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myq6b2b0h primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:remove-formatting-duotone" /></template>
