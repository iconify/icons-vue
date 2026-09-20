<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v397dpzin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v397dpzin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-bold" /></template>
