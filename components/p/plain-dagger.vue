<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao3bdckpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ao3bdckpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plain-dagger" /></template>
