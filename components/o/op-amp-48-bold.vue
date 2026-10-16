<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t85io_b9n.css';
import '../../css/y/yl9kalg0k.css';
import '../../css/f/feujplb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t85io_b9n"/><path class="yl9kalg0k"/><path class="feujplb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:op-amp-48-bold" /></template>
