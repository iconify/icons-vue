<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a57o6o-0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a57o6o-0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-tank" /></template>
