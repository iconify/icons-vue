<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5y65zb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="a5y65zb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:paperplane" /></template>
