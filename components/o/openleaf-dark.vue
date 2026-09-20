<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__a3ub2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q__a3ub2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openleaf-dark" /></template>
