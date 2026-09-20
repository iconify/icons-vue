<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gue-6fjdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gue-6fjdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-triangle-filled" /></template>
