<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d622-7b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d622-7b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vaadin" /></template>
