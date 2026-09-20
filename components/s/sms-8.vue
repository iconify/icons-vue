<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxbx25zyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxbx25zyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-8" /></template>
