<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t48va3bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="t48va3bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:unlock-2" /></template>
