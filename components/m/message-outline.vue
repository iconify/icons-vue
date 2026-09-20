<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t19sicbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="t19sicbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:message-outline" /></template>
