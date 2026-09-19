<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn0lll37g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fn0lll37g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pear" /></template>
