<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac35u9zca.css';
import '../../css/n/n828jkbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ac35u9zca"/><path class="n828jkbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-blade-48-bold" /></template>
