<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq29v9bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq29v9bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pogocache-light" /></template>
