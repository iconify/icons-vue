<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mou448bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mou448bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-7" /></template>
