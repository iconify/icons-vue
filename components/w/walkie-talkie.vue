<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2ngn6fhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t2ngn6fhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:walkie-talkie" /></template>
