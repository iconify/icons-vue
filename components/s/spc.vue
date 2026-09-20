<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krwbbqbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krwbbqbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:spc" /></template>
