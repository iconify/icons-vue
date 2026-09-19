<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqpsy4b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqpsy4b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:terminal" /></template>
