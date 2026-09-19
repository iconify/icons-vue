<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbkmr_byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="rbkmr_byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:viacoin" /></template>
