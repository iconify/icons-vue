<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igfdo3bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igfdo3bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:shield-outline" /></template>
