<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa521w24b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa521w24b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:note-remove" /></template>
