<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqs10by8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqs10by8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matomo-dark" /></template>
