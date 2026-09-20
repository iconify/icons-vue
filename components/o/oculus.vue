<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9960xbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9960xbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:oculus" /></template>
