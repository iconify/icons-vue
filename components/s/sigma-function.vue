<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elv6vybcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elv6vybcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sigma-function" /></template>
