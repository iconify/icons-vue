<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b171b1wiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b171b1wiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pikvm" /></template>
