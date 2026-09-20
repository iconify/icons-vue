<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx-4cl3tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fx-4cl3tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mouse-outline" /></template>
