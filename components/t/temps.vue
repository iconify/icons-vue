<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wajlscekb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wajlscekb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:temps" /></template>
