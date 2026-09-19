<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7fm_bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx7fm_bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:windows-old" /></template>
