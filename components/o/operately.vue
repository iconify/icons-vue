<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgxvy9xdu.css';
import '../../css/o/on1z0j2yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgxvy9xdu"/><path class="on1z0j2yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:operately" /></template>
