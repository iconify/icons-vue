<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v274lh87u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v274lh87u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:validate" /></template>
