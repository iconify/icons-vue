<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anam2owfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anam2owfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webmin-dark" /></template>
