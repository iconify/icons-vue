<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4fjajbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4fjajbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:video-off-fill" /></template>
