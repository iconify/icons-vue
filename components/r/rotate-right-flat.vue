<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aea85dbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aea85dbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:rotate-right-flat" /></template>
