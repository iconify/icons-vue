<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efizyogne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efizyogne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:password-user" /></template>
