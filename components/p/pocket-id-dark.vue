<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be0atlklu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="be0atlklu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket-id-dark" /></template>
