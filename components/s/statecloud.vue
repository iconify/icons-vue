<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k60p3tbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k60p3tbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:statecloud" /></template>
