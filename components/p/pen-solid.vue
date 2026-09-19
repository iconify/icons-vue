<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1su08vhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1su08vhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:pen-solid" /></template>
