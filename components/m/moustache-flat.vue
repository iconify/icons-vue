<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkvx44x9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkvx44x9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:moustache-flat" /></template>
