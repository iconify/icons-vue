<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf8fnpfck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf8fnpfck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-big-right" /></template>
