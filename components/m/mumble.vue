<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb5jeabjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb5jeabjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mumble" /></template>
