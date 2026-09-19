<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n11niyb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n11niyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:three-burning-balls" /></template>
