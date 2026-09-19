<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7p7qz3cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7p7qz3cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:trash-bin-solid" /></template>
