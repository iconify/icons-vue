<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v49u3ub2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v49u3ub2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:polarchart" /></template>
