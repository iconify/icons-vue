<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-939gw4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o-939gw4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pill-bottle-with-rx-symbol" /></template>
