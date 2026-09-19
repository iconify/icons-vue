<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i269neb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i269neb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:periscope" /></template>
