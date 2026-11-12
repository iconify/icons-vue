<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu_s1bbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wu_s1bbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subarr-dark" /></template>
