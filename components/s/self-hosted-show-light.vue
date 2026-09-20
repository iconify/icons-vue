<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asj-_acvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="asj-_acvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:self-hosted-show-light" /></template>
