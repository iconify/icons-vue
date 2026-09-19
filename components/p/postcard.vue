<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsadl7bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dsadl7bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:postcard" /></template>
