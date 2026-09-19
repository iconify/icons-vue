<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhyin5bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1360,"height":1000};
const content = `<path class="nhyin5bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:video" /></template>
