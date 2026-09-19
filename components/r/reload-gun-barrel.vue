<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvw82kb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvw82kb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:reload-gun-barrel" /></template>
