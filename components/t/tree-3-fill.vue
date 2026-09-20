<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg352rb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg352rb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-3-fill" /></template>
