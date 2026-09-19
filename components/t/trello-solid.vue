<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl49b_58y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fl49b_58y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:trello-solid" /></template>
