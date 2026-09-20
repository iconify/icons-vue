<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ah_44wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="t8ah_44wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:square-root" /></template>
