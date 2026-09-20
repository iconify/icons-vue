<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjw90xqmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjw90xqmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-top-light" /></template>
