<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umia02pax.css';
import '../../css/m/md4i0xbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="umia02pax"/><path class="md4i0xbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-up-20-bold" /></template>
