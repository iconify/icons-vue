<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpn1tqbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpn1tqbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:robot" /></template>
