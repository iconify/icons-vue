<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6ul5xvrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ul5xvrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:type-off-solid" /></template>
