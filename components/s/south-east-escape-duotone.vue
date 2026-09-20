<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mir6zs6yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mir6zs6yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-east-escape-duotone" /></template>
