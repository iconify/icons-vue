<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvsq4cc8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lvsq4cc8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-right-fill" /></template>
