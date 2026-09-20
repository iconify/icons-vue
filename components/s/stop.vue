<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkmvasb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nkmvasb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:stop" /></template>
