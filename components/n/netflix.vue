<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe3j3gbqd.css';
import '../../css/u/uruqrcc2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xe3j3gbqd"/><path class="uruqrcc2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netflix" /></template>
