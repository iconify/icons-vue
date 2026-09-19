<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxsqt2g8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lxsqt2g8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:toggle-on-fill" /></template>
