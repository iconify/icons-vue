<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvj6mb8y.css';
import '../../css/n/nb5248_8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gwvj6mb8y"/><path class="nb5248_8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ski-lift-48-bold" /></template>
