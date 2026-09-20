<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqrr_902l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qqrr_902l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-ice-skating" /></template>
