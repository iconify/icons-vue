<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo6_qdb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo6_qdb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stalactites" /></template>
