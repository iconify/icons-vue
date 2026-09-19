<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iukgmv2cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iukgmv2cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:refresh" /></template>
