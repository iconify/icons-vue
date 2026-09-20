<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypl4acb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypl4acb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unraid-light" /></template>
