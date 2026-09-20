<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojv1hdbuc.css';
import '../../css/a/ab03k5swc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojv1hdbuc"/><path class="ab03k5swc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rsshub-dark" /></template>
