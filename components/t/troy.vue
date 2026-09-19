<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqtragb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="mqtragb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:troy" /></template>
