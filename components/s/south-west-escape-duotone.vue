<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnu0hceal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnu0hceal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-west-escape-duotone" /></template>
