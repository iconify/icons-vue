<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb_7qobvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb_7qobvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-fill" /></template>
