<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a15fqzbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a15fqzbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tulip-filled" /></template>
