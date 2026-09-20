<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_77zcccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_77zcccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postcard" /></template>
