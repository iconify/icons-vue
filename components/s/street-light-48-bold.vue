<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be-3goh7n.css';
import '../../css/d/do-2pcc7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="be-3goh7n"/><path class="do-2pcc7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:street-light-48-bold" /></template>
