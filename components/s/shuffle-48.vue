<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhf6nqbcm.css';
import '../../css/k/khmlq3g6t.css';
import '../../css/b/b63ugobgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lhf6nqbcm"/><path class="khmlq3g6t"/><path class="b63ugobgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shuffle-48" /></template>
