<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsh1rl1iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsh1rl1iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:note-add" /></template>
