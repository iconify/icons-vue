<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nceystbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nceystbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shard-sword" /></template>
