<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m--alzbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m--alzbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-west-escape-duotone" /></template>
