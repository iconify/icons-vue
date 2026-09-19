<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndv6oqbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ndv6oqbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:usb" /></template>
