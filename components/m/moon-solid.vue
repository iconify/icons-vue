<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmy114bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmy114bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:moon-solid" /></template>
