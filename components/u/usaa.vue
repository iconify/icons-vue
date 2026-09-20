<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hds94nbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hds94nbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usaa" /></template>
