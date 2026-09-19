<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjhr-bb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjhr-bb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shield-dog" /></template>
