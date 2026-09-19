<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cab465bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cab465bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:service-instance" /></template>
