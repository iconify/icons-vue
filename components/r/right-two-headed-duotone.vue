<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4o2u6vyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4o2u6vyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:right-two-headed-duotone" /></template>
