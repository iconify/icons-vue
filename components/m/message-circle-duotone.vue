<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oav543bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oav543bla primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-duotone" /></template>
