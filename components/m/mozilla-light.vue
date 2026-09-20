<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6jyz04bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6jyz04bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mozilla-light" /></template>
