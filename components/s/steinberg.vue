<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkc7pb9ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkc7pb9ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:steinberg" /></template>
