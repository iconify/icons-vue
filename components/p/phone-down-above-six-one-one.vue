<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swzpzlbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="swzpzlbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-six-one-one" /></template>
