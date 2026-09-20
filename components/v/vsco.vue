<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe6uygbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe6uygbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vsco" /></template>
