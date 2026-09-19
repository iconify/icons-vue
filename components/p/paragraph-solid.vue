<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0aymbc_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0aymbc_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:paragraph-solid" /></template>
