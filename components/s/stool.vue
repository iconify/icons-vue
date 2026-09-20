<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b87-ivmbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b87-ivmbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stool" /></template>
