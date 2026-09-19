<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvr54ob0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvr54ob0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:phone-thin" /></template>
