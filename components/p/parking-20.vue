<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1oumu-ip.css';
import '../../css/d/dx356g9xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a1oumu-ip"/><path class="dx356g9xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parking-20" /></template>
