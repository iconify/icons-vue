<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiq111b5p.css';
import '../../css/y/ybd9n1b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiq111b5p"/><path class="ybd9n1b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:markdown" /></template>
