<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzb7f3prz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzb7f3prz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:viber" /></template>
