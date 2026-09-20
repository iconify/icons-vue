<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6ijttwqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="a6ijttwqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:shuffle" /></template>
