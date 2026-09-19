<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a038dsbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a038dsbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rotate" /></template>
