<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyxjp0w2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyxjp0w2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:viaplay" /></template>
