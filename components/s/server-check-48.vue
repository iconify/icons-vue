<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k71mgzbis.css';
import '../../css/a/a3siao3xy.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k71mgzbis"/><path class="a3siao3xy"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-check-48" /></template>
