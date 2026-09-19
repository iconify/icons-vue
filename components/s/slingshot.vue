<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo6snj8bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo6snj8bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slingshot" /></template>
