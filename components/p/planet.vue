<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc5a15b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bc5a15b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:planet" /></template>
