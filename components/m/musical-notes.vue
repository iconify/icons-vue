<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lytt0db4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="lytt0db4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:musical-notes" /></template>
