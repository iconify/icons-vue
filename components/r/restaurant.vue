<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b87marb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b87marb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:restaurant" /></template>
