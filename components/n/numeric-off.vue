<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_7heqbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_7heqbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-off" /></template>
