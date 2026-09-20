<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw-o6fboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="kw-o6fboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:phone" /></template>
