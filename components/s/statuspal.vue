<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kffj2xutz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kffj2xutz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:statuspal" /></template>
