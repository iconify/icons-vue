<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1zon-i5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1zon-i5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-check-sharp-fill" /></template>
