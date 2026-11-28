<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph83qph3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph83qph3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tag-off-solid" /></template>
