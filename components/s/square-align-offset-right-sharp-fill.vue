<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8t6p8bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8t6p8bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-right-sharp-fill" /></template>
