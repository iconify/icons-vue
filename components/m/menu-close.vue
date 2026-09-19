<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acemr0b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acemr0b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:menu-close" /></template>
