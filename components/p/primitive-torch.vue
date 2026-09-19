<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkt9d2bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kkt9d2bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:primitive-torch" /></template>
