<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oskty9h7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oskty9h7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zaim" /></template>
