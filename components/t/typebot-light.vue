<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbbj9dbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbbj9dbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typebot-light" /></template>
