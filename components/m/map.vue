<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhok3cb9s.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/m/m2huwebvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yhok3cb9s"/><circle class="ob_nbubvj"/><path class="m2huwebvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:map" /></template>
