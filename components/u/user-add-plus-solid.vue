<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn9sdzgym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fn9sdzgym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-add-plus-solid" /></template>
