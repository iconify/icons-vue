<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smu1-736o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smu1-736o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prosody-light" /></template>
