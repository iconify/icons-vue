<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfrkt8eii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfrkt8eii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:network-file-system" /></template>
