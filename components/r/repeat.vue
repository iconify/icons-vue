<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da99er92l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="da99er92l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:repeat" /></template>
