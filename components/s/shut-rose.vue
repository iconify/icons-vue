<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auv0c3bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="auv0c3bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shut-rose" /></template>
