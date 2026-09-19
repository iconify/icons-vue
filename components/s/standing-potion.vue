<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhgy8ebgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhgy8ebgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:standing-potion" /></template>
