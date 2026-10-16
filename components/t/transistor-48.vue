<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu8nygbvh.css';
import '../../css/x/xyjx8qb8q.css';
import '../../css/m/m9bq4cboz.css';
import '../../css/f/ft2875bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hu8nygbvh"/><path class="xyjx8qb8q"/><path class="m9bq4cboz"/><path class="ft2875bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transistor-48" /></template>
