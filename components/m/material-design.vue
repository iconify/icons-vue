<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na_e-8bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na_e-8bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:material-design" /></template>
