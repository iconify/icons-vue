<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9n-v7-5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9n-v7-5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:strongbox" /></template>
