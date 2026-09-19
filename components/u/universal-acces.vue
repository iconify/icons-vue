<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocmpgtb3x.css';
import '../../css/j/j0rk_8u7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocmpgtb3x"/><path class="j0rk_8u7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:universal-acces" /></template>
