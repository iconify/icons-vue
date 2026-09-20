<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsjp5hb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsjp5hb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-leap-dark" /></template>
