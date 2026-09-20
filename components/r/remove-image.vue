<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng2byr-tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ng2byr-tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:remove-image" /></template>
