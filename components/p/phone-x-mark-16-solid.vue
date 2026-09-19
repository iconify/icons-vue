<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ijimd2c.css';
import '../../css/v/vt4x3hbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i6ijimd2c"/><path class="vt4x3hbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:phone-x-mark-16-solid" /></template>
