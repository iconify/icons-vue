<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gezopnizk.css';
import '../../css/p/plqzk5bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gezopnizk"/><path class="plqzk5bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:paypal" /></template>
