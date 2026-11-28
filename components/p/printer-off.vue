<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go_7nmb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go_7nmb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:printer-off" /></template>
