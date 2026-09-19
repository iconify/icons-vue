<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y837vvbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y837vvbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-edit-filled" /></template>
