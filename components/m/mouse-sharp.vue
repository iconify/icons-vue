<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra01bjbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra01bjbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-sharp" /></template>
