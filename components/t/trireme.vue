<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je_3mtapi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="je_3mtapi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trireme" /></template>
