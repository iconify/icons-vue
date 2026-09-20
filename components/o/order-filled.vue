<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmf2iu29k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mmf2iu29k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-filled" /></template>
