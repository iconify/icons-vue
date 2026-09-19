<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-9ezbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="wm-9ezbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:vcard" /></template>
