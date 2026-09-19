<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b556pqxyw.css';
import '../../css/l/l3hxi7bhe.css';
import '../../css/y/y7mxs0lsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b556pqxyw"/><path class="l3hxi7bhe"/><path class="y7mxs0lsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:speedometer-outline" /></template>
