<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo0fe9mij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo0fe9mij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:swatchbook" /></template>
