<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dki4pzb1t.css';
import '../../css/c/clec0e7ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dki4pzb1t"/><path class="clec0e7ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roundcube-dark" /></template>
