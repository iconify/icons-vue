<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4e1bibkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4e1bibkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:thumbs-up" /></template>
