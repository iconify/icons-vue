<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiqj4rbas.css';
import '../../css/z/z0v3o5vsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eiqj4rbas"/><path class="z0v3o5vsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openprinting-cups" /></template>
