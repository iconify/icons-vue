<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg8fvab-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vg8fvab-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-exclamation-solid" /></template>
