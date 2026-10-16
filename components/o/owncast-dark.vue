<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir2n3xb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":96,"height":105};
const content = `<path class="ir2n3xb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:owncast-dark" /></template>
