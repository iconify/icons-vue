<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgfxe3bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgfxe3bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-top-sharp-fill" /></template>
