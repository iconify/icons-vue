<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7kpuwdxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7kpuwdxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stopstalk" /></template>
