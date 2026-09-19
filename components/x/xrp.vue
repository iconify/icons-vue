<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk9xfo3pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pk9xfo3pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:xrp" /></template>
