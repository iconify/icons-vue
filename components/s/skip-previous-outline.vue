<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq8mcibiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oq8mcibiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-previous-outline" /></template>
