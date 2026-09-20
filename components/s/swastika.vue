<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2uaob4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rp2uaob4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:swastika" /></template>
