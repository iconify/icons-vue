<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1uftcb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p1uftcb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:monorail-transit-vehicle-with-destination-display" /></template>
