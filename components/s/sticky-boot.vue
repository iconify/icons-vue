<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btpm_6era.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="btpm_6era"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sticky-boot" /></template>
