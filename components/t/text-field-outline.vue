<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffu3be33e.css';
import '../../css/e/e91nqrblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffu3be33e"/><path clip-rule="evenodd" class="e91nqrblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-field-outline" /></template>
