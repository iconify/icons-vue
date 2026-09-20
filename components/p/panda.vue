<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxtq6hf-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxtq6hf-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:panda" /></template>
