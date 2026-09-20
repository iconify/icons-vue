<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwe4qbolb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwe4qbolb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:quasar" /></template>
