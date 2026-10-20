<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siepju6rr.css';
import '../../css/o/o2a3vtbnh.css';
import '../../css/p/p6ygvpb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="siepju6rr"/><path class="o2a3vtbnh"/><path class="p6ygvpb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:test-tube-48-bold" /></template>
