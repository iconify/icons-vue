<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo28_rb7q.css';
import '../../css/a/a67_ne9yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo28_rb7q"/><path class="a67_ne9yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:nut-off-filled" /></template>
