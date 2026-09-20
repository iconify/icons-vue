<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzy3mpo1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="vzy3mpo1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:news" /></template>
