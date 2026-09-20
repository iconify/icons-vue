<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt0guk9-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt0guk9-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xsplit" /></template>
