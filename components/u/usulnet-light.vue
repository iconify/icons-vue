<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfqh065wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfqh065wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usulnet-light" /></template>
