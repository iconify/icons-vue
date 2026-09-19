<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyxbc2xdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyxbc2xdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slumbering-sanctuary" /></template>
