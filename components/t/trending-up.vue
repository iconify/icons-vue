<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fep7b50pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fep7b50pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:trending-up" /></template>
