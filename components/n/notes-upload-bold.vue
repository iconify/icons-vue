<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teryzmwzf.css';
import '../../css/f/f1vawn50g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teryzmwzf"/><path class="f1vawn50g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:notes-upload-bold" /></template>
