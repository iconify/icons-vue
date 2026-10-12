<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnt0aoe9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jnt0aoe9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tram-front-filled" /></template>
