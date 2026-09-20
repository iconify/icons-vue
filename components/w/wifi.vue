<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aetlc5bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aetlc5bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wifi" /></template>
