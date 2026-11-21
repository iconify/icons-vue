<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui6tf0b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ui6tf0b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:relaticle" /></template>
