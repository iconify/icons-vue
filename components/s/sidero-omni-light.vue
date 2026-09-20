<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnqs0lbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnqs0lbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sidero-omni-light" /></template>
