<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oln8vpg8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oln8vpg8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:thumbtack-outline" /></template>
