<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mej-j8b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mej-j8b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zenn" /></template>
