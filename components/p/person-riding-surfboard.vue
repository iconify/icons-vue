<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu3lc0a4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pu3lc0a4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-riding-surfboard" /></template>
