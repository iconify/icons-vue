<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouv-3on5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouv-3on5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-x-filled" /></template>
