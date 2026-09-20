<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j82ak5bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j82ak5bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sparkfun" /></template>
