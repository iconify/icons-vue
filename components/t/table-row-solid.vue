<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9435tbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t9435tbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:table-row-solid" /></template>
