<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2o5zgssc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t2o5zgssc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-balancing-on-low-mounted-beam" /></template>
