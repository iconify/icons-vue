<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsjcdtb3y.css';
import '../../css/s/s6s6d1bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsjcdtb3y"/><path class="s6s6d1bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sendgrid-light" /></template>
