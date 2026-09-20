<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoy-4cccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qoy-4cccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rachio-light" /></template>
