<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upq40fb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upq40fb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-info" /></template>
