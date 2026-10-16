<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8dezzb1i.css';
import '../../css/x/x5bj1qhem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s8dezzb1i"/><path class="x5bj1qhem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:winch-20" /></template>
