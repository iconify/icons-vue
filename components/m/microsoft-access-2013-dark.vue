<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1os0n7nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1os0n7nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-2013-dark" /></template>
