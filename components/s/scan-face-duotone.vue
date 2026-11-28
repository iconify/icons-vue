<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu2jnacmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu2jnacmk primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-face-duotone" /></template>
