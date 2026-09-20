<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eest8db3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="eest8db3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:wedding-cake" /></template>
