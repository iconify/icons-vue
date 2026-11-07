<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9iqk5btj.css';
import '../../css/u/upjyccctb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9iqk5btj"/><path clip-rule="evenodd" class="upjyccctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-bold" /></template>
