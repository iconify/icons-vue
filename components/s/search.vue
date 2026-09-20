<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ret9ytbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ret9ytbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:search" /></template>
