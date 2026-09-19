<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgjqpvbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pgjqpvbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:webstorm" /></template>
