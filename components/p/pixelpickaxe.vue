<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdvvetb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rdvvetb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelpickaxe" /></template>
