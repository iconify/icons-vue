<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkh8yvkml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkh8yvkml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-minus-filled" /></template>
