<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p38alfs4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="p38alfs4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:projectcompare" /></template>
