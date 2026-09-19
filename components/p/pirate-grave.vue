<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz__e2bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lz__e2bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pirate-grave" /></template>
