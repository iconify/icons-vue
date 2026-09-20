<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3os1xhir.css';
import '../../css/w/wjlktkbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3os1xhir"/><path class="wjlktkbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:temperature-thermometer-medium-bold" /></template>
