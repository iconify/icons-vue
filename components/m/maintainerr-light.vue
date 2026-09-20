<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh-kc6bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eh-kc6bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maintainerr-light" /></template>
