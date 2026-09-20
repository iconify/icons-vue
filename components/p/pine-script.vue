<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmbb1eb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmbb1eb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pine-script" /></template>
