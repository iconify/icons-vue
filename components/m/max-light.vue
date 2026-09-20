<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4k-61htt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4k-61htt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:max-light" /></template>
