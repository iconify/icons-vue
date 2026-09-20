<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg9rrk_dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bg9rrk_dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toggle-on-sharp-fill" /></template>
