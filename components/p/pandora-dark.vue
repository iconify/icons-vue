<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0t9c4vnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s0t9c4vnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pandora-dark" /></template>
