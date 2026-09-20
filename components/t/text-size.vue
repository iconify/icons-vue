<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we6n59b6n.css';
import '../../css/n/nmu_9kcuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="we6n59b6n"/><path class="nmu_9kcuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:text-size" /></template>
