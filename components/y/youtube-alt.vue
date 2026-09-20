<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdabxtboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdabxtboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:youtube-alt" /></template>
