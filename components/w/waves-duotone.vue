<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df8v87a8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df8v87a8v primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waves-duotone" /></template>
