<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm7nzo8xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm7nzo8xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:swap-horiz-line" /></template>
