<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xenzbobje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xenzbobje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:zoom-out-filled" /></template>
