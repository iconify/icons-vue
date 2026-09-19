<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqj0bns5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqj0bns5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:schrodingers-cat-alive" /></template>
