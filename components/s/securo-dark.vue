<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dks3jibad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dks3jibad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:securo-dark" /></template>
