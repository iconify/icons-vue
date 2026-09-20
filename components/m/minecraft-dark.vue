<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmks9jq-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmks9jq-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minecraft-dark" /></template>
