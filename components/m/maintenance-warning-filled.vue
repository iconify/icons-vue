<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y75k9vb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y75k9vb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-warning-filled" /></template>
