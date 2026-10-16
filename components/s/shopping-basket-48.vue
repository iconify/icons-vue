<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5vym_8fp.css';
import '../../css/z/z3ml8sb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k5vym_8fp"/><path class="z3ml8sb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shopping-basket-48" /></template>
