<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5a6n0a1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b5a6n0a1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:swift" /></template>
