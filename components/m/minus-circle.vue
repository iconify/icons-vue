<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlg6dlbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlg6dlbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:minus-circle" /></template>
