<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txh3d43br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txh3d43br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square" /></template>
