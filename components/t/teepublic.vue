<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8y4s4lst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8y4s4lst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:teepublic" /></template>
