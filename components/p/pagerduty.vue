<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvxma1b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvxma1b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pagerduty" /></template>
