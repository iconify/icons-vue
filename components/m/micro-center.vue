<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_idavemy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_idavemy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:micro-center" /></template>
