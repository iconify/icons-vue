<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnv6n6bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnv6n6bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shield-check-solid" /></template>
