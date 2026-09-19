<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwx73ffxg.css';
import '../../css/e/egqw4un5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kwx73ffxg"/><path class="egqw4un5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:openfolder" /></template>
