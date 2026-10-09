<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5f709d9b.css';
import '../../css/g/gapv30tqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k5f709d9b"/><path class="gapv30tqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltmeter-20-bold" /></template>
