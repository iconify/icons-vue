<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxckild9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="nxckild9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:reddit" /></template>
