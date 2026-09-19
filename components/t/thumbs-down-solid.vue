<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txvnc3bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txvnc3bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:thumbs-down-solid" /></template>
