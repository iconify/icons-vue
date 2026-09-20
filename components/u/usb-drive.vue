<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_yv6gb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_yv6gb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:usb-drive" /></template>
