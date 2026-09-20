<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_-kfbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae_-kfbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:private-internet-access-light" /></template>
