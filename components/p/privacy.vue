<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgack7b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="jgack7b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:privacy" /></template>
