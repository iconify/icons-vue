<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8fvfdcfq.css';
import '../../css/n/n9js5qbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m8fvfdcfq"/><path class="n9js5qbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pin-20" /></template>
