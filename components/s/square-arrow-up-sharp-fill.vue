<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4kdf1bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4kdf1bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-up-sharp-fill" /></template>
