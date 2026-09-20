<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxog6t6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hrxog6t6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:om-on-square" /></template>
