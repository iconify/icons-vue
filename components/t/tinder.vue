<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-8-v7nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh-8-v7nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tinder" /></template>
