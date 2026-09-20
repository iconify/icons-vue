<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ssq09rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="x4ssq09rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:rfidtag" /></template>
