<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn0uyxwmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn0uyxwmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:perl" /></template>
