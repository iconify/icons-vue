<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n78-1ulvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n78-1ulvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:universal-access-solid" /></template>
