<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0f1b5b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0f1b5b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:swiss" /></template>
