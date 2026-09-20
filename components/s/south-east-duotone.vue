<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuph2izvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuph2izvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-east-duotone" /></template>
