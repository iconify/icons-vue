<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orps6sbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orps6sbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pubg" /></template>
