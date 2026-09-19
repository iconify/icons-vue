<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbgz-if8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbgz-if8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-outline" /></template>
