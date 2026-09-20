<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu-w_8f-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu-w_8f-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:pentagon-flat" /></template>
