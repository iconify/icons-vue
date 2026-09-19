<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3npp-y-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3npp-y-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:transparent-tubes" /></template>
