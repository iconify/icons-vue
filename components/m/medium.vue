<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqoargbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqoargbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:medium" /></template>
