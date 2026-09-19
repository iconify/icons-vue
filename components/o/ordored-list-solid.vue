<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p71oiqb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p71oiqb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:ordored-list-solid" /></template>
