<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkr1c6dyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkr1c6dyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-0" /></template>
