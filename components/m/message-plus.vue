<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrd5ojx6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrd5ojx6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-plus" /></template>
