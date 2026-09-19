<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scqqs5yey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="scqqs5yey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:menu-alt-01" /></template>
