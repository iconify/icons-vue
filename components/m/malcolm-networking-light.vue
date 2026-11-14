<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5ao3bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="un5ao3bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:malcolm-networking-light" /></template>
