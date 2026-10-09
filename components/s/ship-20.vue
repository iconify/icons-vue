<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnpp6kxet.css';
import '../../css/o/o1nbqcbpn.css';
import '../../css/k/k8gd1dj3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fnpp6kxet"/><path class="o1nbqcbpn"/><path class="k8gd1dj3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ship-20" /></template>
