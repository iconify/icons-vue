<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9bygdc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g9bygdc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:package-dimension-remix" /></template>
