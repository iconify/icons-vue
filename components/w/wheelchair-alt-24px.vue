<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwn7tqbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwn7tqbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:wheelchair-alt-24px" /></template>
