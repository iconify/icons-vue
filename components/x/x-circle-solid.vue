<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbem7bc9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbem7bc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:x-circle-solid" /></template>
