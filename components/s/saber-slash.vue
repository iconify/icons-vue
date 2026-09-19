<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxt5wfc_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxt5wfc_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:saber-slash" /></template>
