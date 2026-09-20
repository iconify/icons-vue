<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cou1a1nam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cou1a1nam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:threema" /></template>
