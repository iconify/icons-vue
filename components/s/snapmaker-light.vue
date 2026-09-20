<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov7nzn2wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ov7nzn2wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapmaker-light" /></template>
