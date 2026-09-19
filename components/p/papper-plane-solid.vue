<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyeo0eqpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyeo0eqpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:papper-plane-solid" /></template>
