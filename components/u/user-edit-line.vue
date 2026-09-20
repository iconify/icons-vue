<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukszzeb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukszzeb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-edit-line" /></template>
