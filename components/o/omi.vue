<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol67_6b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol67_6b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:omi" /></template>
