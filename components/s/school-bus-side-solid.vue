<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4mz7cb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4mz7cb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:school-bus-side-solid" /></template>
