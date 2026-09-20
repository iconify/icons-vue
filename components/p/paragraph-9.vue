<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7zp-dbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7zp-dbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:paragraph-9" /></template>
