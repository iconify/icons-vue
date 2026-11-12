<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td42iq_wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="td42iq_wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sipeed-light" /></template>
