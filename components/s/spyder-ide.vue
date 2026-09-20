<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4p1ad74m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4p1ad74m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spyder-ide" /></template>
