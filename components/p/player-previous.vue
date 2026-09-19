<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9-mh3b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y9-mh3b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:player-previous" /></template>
