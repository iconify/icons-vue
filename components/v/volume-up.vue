<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p39g-b1jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="p39g-b1jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:volume-up" /></template>
