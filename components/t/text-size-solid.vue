<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmf13t2li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmf13t2li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:text-size-solid" /></template>
