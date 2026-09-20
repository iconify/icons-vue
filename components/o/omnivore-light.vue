<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqip0ibbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqip0ibbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnivore-light" /></template>
