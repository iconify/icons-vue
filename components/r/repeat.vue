<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpf0o4buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpf0o4buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:repeat" /></template>
