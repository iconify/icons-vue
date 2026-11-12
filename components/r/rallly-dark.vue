<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9woi6bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9woi6bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rallly-dark" /></template>
