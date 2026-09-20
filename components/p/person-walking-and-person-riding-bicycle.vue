<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbh-kn0cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mbh-kn0cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-and-person-riding-bicycle" /></template>
