<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umyqa91-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="umyqa91-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:southwest-airlines-light" /></template>
