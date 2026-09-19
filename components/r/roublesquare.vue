<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy_iepb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="dy_iepb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:roublesquare" /></template>
