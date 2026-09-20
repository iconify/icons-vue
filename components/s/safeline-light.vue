<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzthh7bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzthh7bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:safeline-light" /></template>
