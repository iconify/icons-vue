<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2mjtcb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j2mjtcb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stackshare" /></template>
