<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubob10ayu.css';
import '../../css/t/tl4woi6ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubob10ayu"/><path class="tl4woi6ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:medal" /></template>
