<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxmoo7dca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxmoo7dca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:point-up-filled" /></template>
