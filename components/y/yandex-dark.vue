<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve1tpjbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ve1tpjbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yandex-dark" /></template>
