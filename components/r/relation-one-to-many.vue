<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzgea5uph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzgea5uph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-one-to-many" /></template>
