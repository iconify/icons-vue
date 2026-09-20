<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7oixqbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="x7oixqbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:volume-mute" /></template>
