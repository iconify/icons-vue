<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7djkybhz.css';
import '../../css/e/e8i4n37kj.css';
import '../../css/z/z0ps7ybaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l7djkybhz"/><path class="e8i4n37kj"/><path class="z0ps7ybaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scaffolding-20-bold" /></template>
